<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbefc9bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wbefc9bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:menu" /></template>
