<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd7besbrf.css';
import '../../css/k/kgg90w3zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd7besbrf"/><path class="kgg90w3zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-information-filled" /></template>
