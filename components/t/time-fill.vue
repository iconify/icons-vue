<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3k2p-2sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3k2p-2sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:time-fill" /></template>
