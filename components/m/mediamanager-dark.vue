<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxxptl7ss.css';
import '../../css/x/xzdvdubue.css';
import '../../css/c/cmmtxw9or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xxxptl7ss"/><path class="xzdvdubue"/><path class="cmmtxw9or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediamanager-dark" /></template>
