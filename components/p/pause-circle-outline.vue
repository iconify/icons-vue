<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weq3zzqer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="weq3zzqer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pause-circle-outline" /></template>
