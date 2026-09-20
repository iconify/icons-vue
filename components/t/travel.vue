<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfcz1lb7w.css';
import '../../css/t/tigdgqbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qfcz1lb7w"/><path class="tigdgqbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:travel" /></template>
