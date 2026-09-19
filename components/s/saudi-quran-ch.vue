<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi_4xcbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi_4xcbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:saudi-quran-ch" /></template>
