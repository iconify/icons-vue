<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc_nxd5hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc_nxd5hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tape-filled" /></template>
