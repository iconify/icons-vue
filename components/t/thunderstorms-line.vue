<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt7pqt42k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt7pqt42k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:thunderstorms-line" /></template>
