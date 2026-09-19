<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgz6g14qr.css';
import '../../css/b/bwy1ik_nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="wgz6g14qr"/><path class="bwy1ik_nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:motorcycle" /></template>
