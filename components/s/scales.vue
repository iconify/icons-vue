<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbg954-7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xbg954-7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:scales" /></template>
