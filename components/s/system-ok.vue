<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syd3mvaxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syd3mvaxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:system-ok" /></template>
