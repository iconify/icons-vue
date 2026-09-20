<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrtf_jb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrtf_jb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:wifi-sync" /></template>
