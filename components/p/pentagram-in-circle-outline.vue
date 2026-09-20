<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2nzhhb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m2nzhhb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pentagram-in-circle-outline" /></template>
