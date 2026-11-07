<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6agol35u.css';
import '../../css/p/pd8yij20i.css';
import '../../css/x/xrgtxcs3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6agol35u"/><path class="pd8yij20i"/><path clip-rule="evenodd" class="xrgtxcs3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:window-frame-bold" /></template>
