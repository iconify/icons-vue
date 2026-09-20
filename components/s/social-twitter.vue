<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p95pe0_jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p95pe0_jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-twitter" /></template>
