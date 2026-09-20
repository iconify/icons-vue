<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw11f-2rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uw11f-2rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle" /></template>
