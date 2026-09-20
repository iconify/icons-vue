<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipdg89bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipdg89bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-wifi-3-fill" /></template>
