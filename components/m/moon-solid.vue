<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsxk-l3nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsxk-l3nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:moon-solid" /></template>
