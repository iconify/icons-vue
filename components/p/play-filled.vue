<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqp4cw_dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nqp4cw_dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:play-filled" /></template>
