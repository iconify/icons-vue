<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt8b9db9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="vt8b9db9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:move-alt" /></template>
