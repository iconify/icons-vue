<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrtfxtn_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrtfxtn_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-locked-line" /></template>
