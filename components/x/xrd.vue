<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc2fn6mkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc2fn6mkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xrd" /></template>
