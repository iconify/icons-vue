<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni1xpsbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni1xpsbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:signature-2-fill" /></template>
