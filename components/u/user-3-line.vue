<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekqss994v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekqss994v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-3-line" /></template>
