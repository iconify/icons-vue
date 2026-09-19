<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnu6c421i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dnu6c421i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-contact" /></template>
