<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kijpecbmw.css';
import '../../css/c/c-2glzb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kijpecbmw"/><path class="c-2glzb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:send-line" /></template>
