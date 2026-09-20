<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljk3adyvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ljk3adyvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mug" /></template>
