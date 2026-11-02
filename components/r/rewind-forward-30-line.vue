<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm782obmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm782obmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-30-line" /></template>
