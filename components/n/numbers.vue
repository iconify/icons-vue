<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw_2mw1yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xw_2mw1yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:numbers" /></template>
