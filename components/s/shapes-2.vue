<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoa3gfyyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoa3gfyyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-2" /></template>
