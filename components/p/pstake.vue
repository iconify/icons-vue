<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgevw-brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgevw-brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pstake" /></template>
