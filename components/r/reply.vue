<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvay3xbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvay3xbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:reply" /></template>
