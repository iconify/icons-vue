<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-c86pphd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-c86pphd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nextcloud" /></template>
