<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj_rx7aix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yj_rx7aix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:planet2-filled" /></template>
