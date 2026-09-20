<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq_-3f6bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq_-3f6bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:timer-alt-filled" /></template>
