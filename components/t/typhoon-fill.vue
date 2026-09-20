<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0l7hg_sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0l7hg_sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:typhoon-fill" /></template>
