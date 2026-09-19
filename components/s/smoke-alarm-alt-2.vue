<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au88_79si.css';
import '../../css/x/x76_u45ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au88_79si"/><path class="x76_u45ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:smoke-alarm-alt-2" /></template>
