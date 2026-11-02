<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xainp7b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xainp7b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:red-packet-open-line" /></template>
