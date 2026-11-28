<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivmqp4-dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivmqp4-dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-minus-solid" /></template>
