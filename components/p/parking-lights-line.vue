<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztgj2k7_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztgj2k7_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:parking-lights-line" /></template>
