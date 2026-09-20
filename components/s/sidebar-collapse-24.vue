<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g325givei.css';
import '../../css/z/z9rr_ubxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g325givei"/><path class="z9rr_ubxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sidebar-collapse-24" /></template>
