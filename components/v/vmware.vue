<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqre6ibnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqre6ibnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vmware" /></template>
