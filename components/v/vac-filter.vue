<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anrso3m5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anrso3m5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vac-filter" /></template>
