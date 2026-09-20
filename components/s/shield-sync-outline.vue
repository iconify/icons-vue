<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wptayz63k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wptayz63k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-sync-outline" /></template>
