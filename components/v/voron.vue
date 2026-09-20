<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brtc7-a1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="brtc7-a1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voron" /></template>
