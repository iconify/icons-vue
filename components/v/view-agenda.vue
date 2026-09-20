<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztdnacbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztdnacbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-agenda" /></template>
