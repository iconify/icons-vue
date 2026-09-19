<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7n7f3ipf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7n7f3ipf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:vimeo-fill" /></template>
