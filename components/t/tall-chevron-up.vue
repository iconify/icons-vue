<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m86xyuyka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m86xyuyka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tall-chevron-up" /></template>
