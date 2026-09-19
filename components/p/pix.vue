<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1kfjobtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i1kfjobtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:pix" /></template>
