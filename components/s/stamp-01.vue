<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frxx8dk-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frxx8dk-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stamp-01" /></template>
