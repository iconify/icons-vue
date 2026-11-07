<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjh_qrbin.css';
import '../../css/q/qnadq5bgl.css';
import '../../css/o/o8qapdbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjh_qrbin"/><path class="qnadq5bgl"/><path class="o8qapdbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-high-bold" /></template>
