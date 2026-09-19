<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ockyt989s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1408};
const content = `<path class="ockyt989s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:unlock" /></template>
