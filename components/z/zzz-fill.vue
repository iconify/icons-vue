<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp1_m2brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp1_m2brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:zzz-fill" /></template>
