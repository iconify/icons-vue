<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lijijvxoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lijijvxoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vr-goggles-filled" /></template>
