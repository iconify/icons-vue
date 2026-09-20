<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dumluac4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dumluac4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:pipe" /></template>
