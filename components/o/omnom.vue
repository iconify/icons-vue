<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3n-n5b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3n-n5b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omnom" /></template>
