<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7o7g3z9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7o7g3z9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:memories-fill" /></template>
