<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk4ccbdmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk4ccbdmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tether-usdt" /></template>
