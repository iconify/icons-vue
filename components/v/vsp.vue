<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiv2irb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiv2irb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vsp" /></template>
