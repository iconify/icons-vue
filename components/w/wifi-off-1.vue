<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc0kr9btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc0kr9btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wifi-off-1" /></template>
