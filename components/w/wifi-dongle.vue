<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccwa-fbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccwa-fbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wifi-dongle" /></template>
