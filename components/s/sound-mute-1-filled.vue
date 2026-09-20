<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvyojlb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvyojlb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sound-mute-1-filled" /></template>
