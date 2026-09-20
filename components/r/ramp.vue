<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szy26opxx.css';
import '../../css/c/csou2mbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szy26opxx"/><path class="csou2mbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ramp" /></template>
