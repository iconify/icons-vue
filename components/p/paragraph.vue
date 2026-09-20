<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz_4febja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jz_4febja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:paragraph" /></template>
