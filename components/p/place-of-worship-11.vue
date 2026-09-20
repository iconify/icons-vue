<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehybqib_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ehybqib_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:place-of-worship-11" /></template>
