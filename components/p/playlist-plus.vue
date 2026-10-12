<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9yynlbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9yynlbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:playlist-plus" /></template>
