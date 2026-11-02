<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkmpimb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkmpimb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sagittarius-line" /></template>
