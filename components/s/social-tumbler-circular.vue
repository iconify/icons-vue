<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc0e-ibjd.css';
import '../../css/y/ye74rhbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc0e-ibjd"/><path class="ye74rhbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-tumbler-circular" /></template>
