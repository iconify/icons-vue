<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnj6icb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnj6icb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:variable" /></template>
