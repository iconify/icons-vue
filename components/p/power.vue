<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qossc8ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qossc8ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:power" /></template>
