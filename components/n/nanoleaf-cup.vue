<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_mk4lb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_mk4lb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-cup" /></template>
