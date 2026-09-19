<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arvx1qb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arvx1qb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:recessed-ceiling" /></template>
