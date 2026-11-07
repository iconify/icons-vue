<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqrhevbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xqrhevbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-down-outline" /></template>
