<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytg06bcnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ytg06bcnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:zoom-out" /></template>
