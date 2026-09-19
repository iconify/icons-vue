<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0bay2vht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b0bay2vht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-heart-empty" /></template>
