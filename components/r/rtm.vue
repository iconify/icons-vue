<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r58y-acsy.css';
import '../../css/x/xqiik-79j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r58y-acsy"/><path class="xqiik-79j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rtm" /></template>
