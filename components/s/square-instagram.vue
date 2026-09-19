<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j88t_ybxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j88t_ybxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-instagram" /></template>
