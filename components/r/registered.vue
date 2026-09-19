<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adhe8lbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="adhe8lbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:registered" /></template>
