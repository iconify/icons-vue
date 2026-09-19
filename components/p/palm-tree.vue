<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iubo3_f_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iubo3_f_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:palm-tree" /></template>
