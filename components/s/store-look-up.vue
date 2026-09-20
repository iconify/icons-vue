<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bywelmzvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bywelmzvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-look-up" /></template>
