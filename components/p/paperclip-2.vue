<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uci1gs-og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uci1gs-og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:paperclip-2" /></template>
