<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq95wcbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jq95wcbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:playlist-2-fill" /></template>
