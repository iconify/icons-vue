<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpg2ybbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpg2ybbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:paint" /></template>
