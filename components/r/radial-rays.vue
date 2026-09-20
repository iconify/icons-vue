<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r51ckzluf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r51ckzluf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:radial-rays" /></template>
