<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw1h23mpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw1h23mpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-f-filled" /></template>
