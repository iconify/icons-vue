<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3_ia3bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="e3_ia3bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:slidersfull" /></template>
