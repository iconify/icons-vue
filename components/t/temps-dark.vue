<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr3savbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tr3savbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:temps-dark" /></template>
