<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utb9dqwgn.css';
import '../../css/m/mq3padcvo.css';
import '../../css/g/gpfk4wrwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utb9dqwgn"/><path class="mq3padcvo"/><path class="gpfk4wrwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vlxpad" /></template>
