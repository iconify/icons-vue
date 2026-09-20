<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3u6_3b8i.css';
import '../../css/f/fg0j46bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3u6_3b8i"/><path class="fg0j46bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:sync-exclamation" /></template>
