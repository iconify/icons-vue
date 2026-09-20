<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg97eobzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gg97eobzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:share-square-solid" /></template>
