<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh_r0wb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dh_r0wb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:playstation" /></template>
