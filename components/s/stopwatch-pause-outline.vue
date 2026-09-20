<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs2csdkir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs2csdkir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stopwatch-pause-outline" /></template>
