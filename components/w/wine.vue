<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg168wb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg168wb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:wine" /></template>
