<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/typ9t6dud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="typ9t6dud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:open-mouth-filled" /></template>
