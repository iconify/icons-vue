<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0biiu03p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="a0biiu03p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:marker-11" /></template>
