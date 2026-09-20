<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csn_ierpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csn_ierpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sparkles-2-off" /></template>
