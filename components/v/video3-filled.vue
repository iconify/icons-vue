<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhp46wbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhp46wbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video3-filled" /></template>
