<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn8jj4b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sn8jj4b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:zoom" /></template>
