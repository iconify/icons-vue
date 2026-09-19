<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp_m6ccqt.css';
import '../../css/w/w9zfbqsgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp_m6ccqt"/><path class="w9zfbqsgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:webstorm" /></template>
