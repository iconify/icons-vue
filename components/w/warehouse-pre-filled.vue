<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lae5htber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lae5htber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:warehouse-pre-filled" /></template>
