<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wta7eoblc.css';
import '../../css/y/ywgw6ib8n.css';
import '../../css/o/o5mwc3v0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="wta7eoblc"/><path class="ywgw6ib8n"/><path class="o5mwc3v0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:switzerland" /></template>
