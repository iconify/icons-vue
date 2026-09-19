<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icn6rqond.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="icn6rqond"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:upload-stroke-16" /></template>
