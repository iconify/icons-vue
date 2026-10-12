<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esg4p2r4f.css';
import '../../css/d/dmxnto4mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esg4p2r4f"/><path class="dmxnto4mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:vibrate-off-filled" /></template>
