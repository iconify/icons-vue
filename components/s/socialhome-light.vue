<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlt9o_vzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zlt9o_vzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:socialhome-light" /></template>
