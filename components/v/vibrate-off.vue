<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnnbavbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnnbavbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:vibrate-off" /></template>
