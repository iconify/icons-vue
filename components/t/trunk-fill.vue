<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iblp2qmfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iblp2qmfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trunk-fill" /></template>
