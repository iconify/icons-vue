<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk-n75bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dk-n75bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:prescription-pills-drugs-healthcare" /></template>
