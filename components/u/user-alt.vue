<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_5p8ly8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z_5p8ly8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-alt" /></template>
