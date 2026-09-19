<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr9efjb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr9efjb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:merx-ipc-horizon-dome" /></template>
