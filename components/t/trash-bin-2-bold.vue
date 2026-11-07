<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-9z98bit.css';
import '../../css/w/wl_vulm8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-9z98bit"/><path class="wl_vulm8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:trash-bin-2-bold" /></template>
