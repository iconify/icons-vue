<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvp10ccvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvp10ccvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:vlc-logo-bold" /></template>
