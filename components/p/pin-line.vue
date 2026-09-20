<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq98o4baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq98o4baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pin-line" /></template>
