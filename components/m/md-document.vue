<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxy8xtbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxy8xtbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-document" /></template>
