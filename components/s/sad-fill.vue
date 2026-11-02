<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hymlktbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hymlktbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sad-fill" /></template>
