<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwghz05gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwghz05gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:meter-cube" /></template>
