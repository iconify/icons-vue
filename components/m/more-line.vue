<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpjleyb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpjleyb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:more-line" /></template>
