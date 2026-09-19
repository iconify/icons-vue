<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux6yzsbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux6yzsbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:touch-08" /></template>
