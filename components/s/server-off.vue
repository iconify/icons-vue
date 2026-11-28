<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyu_nlhsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyu_nlhsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:server-off" /></template>
