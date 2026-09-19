<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmo20pbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmo20pbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:small-lamp" /></template>
