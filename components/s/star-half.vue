<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn1wbx3yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn1wbx3yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:star-half" /></template>
