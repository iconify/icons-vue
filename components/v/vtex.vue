<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6360bb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6360bb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vtex" /></template>
