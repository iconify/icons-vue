<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lint33bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lint33bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pbs-kids" /></template>
