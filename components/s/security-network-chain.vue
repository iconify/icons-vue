<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoya6dbao.css';
import '../../css/m/m5l3mnb5w.css';
import '../../css/j/j_tp7ieis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoya6dbao"/><path class="m5l3mnb5w"/><path class="j_tp7ieis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:security-network-chain" /></template>
