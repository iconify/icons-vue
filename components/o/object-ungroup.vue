<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwmnbk0gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1792};
const content = `<path class="xwmnbk0gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:object-ungroup" /></template>
