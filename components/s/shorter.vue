<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaaat3jqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uaaat3jqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shorter" /></template>
