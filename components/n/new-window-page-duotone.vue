<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frp_v-l8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frp_v-l8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:new-window-page-duotone" /></template>
