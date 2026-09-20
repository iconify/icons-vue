<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkr0r0bta.css';
import '../../css/q/qw6hk3bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkr0r0bta"/><path class="qw6hk3bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:train-3-line" /></template>
