<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p206_ts3m.css';
import '../../css/u/u3j01bgpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p206_ts3m secondary"/><path class="primary u3j01bgpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:navigation-duo" /></template>
