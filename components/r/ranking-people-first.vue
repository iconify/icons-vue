<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhb9inq-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhb9inq-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ranking-people-first" /></template>
