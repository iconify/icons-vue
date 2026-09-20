<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba63usbyw.css';
import '../../css/f/f3e8vhbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba63usbyw"/><path class="f3e8vhbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:slr" /></template>
