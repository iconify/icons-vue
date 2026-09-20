<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv16btbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv16btbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:soap-dispenser-droplet" /></template>
