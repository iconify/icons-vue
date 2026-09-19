<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtc0jqpcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="rtc0jqpcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:progress-7" /></template>
