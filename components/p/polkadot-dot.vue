<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb-zqxblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb-zqxblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:polkadot-dot" /></template>
