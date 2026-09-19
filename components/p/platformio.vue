<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5uqnmb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":425,"height":512};
const content = `<path class="g5uqnmb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:platformio" /></template>
