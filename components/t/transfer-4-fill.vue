<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am30hdbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am30hdbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-4-fill" /></template>
