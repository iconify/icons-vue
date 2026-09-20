<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu0_hdbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pu0_hdbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:stop" /></template>
