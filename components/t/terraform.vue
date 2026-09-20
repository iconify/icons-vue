<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw_7_gbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw_7_gbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:terraform" /></template>
