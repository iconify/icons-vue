<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf9l5ddip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jf9l5ddip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:stethoscope" /></template>
