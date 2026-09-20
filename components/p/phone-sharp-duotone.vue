<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruxv4vbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruxv4vbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-sharp-duotone" /></template>
