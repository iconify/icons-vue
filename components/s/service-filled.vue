<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqu85rp4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqu85rp4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:service-filled" /></template>
