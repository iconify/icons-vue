<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv4cjgadb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv4cjgadb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pagespeed-insights" /></template>
