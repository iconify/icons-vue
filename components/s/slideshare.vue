<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k31-o_b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":424,"height":432};
const content = `<path class="k31-o_b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:slideshare" /></template>
