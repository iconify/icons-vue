<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndjxw_bam.css';
import '../../css/p/p2vf_po5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ndjxw_bam"/><path class="p2vf_po5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:space" /></template>
