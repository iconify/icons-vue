<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_jmlxnvx.css';
import '../../css/m/mza_fjbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer s_jmlxnvx"/><path class="duoicon-secondary-layer mza_fjbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:user" /></template>
