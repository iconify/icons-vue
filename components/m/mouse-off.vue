<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibjd-og5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibjd-og5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-off" /></template>
