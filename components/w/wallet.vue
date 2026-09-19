<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq0wx8bxg.css';
import '../../css/s/sczabacxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq0wx8bxg"/><path class="sczabacxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:wallet" /></template>
