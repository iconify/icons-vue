<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qetnckbkp.css';
import '../../css/y/ya1w5kb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qetnckbkp"/><path class="ya1w5kb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:silhouetteohjapan" /></template>
