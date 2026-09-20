<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0iol_2th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0iol_2th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:page-previous" /></template>
