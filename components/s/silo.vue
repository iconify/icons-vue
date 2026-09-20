<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzwk-5byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gzwk-5byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:silo" /></template>
