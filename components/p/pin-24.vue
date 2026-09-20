<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atvq_qble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atvq_qble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pin-24" /></template>
