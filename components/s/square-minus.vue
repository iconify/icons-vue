<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef7owseox.css';
import '../../css/z/zan_i8btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef7owseox"/><path class="zan_i8btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:square-minus" /></template>
