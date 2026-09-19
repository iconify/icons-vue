<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci595pbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ci595pbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:record" /></template>
