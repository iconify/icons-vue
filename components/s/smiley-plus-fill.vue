<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gal76s2ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gal76s2ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:smiley-plus-fill" /></template>
