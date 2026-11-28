<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slknnlbbl.css';
import '../../css/s/s8ywqlbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary slknnlbbl"/><path class="primary s8ywqlbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:octagon-duo" /></template>
