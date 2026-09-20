<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fehezhbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fehezhbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-square-outline-with-dot" /></template>
