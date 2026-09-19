<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lebas9t0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lebas9t0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:qnap-rtorrent-pro" /></template>
