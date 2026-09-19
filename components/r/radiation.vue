<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssy6g0bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssy6g0bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:radiation" /></template>
