<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwde3obxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uwde3obxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:vip-consume-filled" /></template>
