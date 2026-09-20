<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmz2-lxle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmz2-lxle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pin-alt-1-line" /></template>
