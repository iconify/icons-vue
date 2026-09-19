<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bunjq_6_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bunjq_6_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:spotify" /></template>
