<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1raw9-zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1raw9-zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-3-lock" /></template>
