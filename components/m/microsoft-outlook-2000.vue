<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za41vfpmx.css';
import '../../css/d/dfdvapbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="za41vfpmx"/><path class="dfdvapbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2000" /></template>
