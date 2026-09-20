<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td2hy69fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td2hy69fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:minus" /></template>
