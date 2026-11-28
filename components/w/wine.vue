<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_94e1ufu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_94e1ufu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wine" /></template>
