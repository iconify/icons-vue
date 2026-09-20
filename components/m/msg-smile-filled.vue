<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvfoi7ylk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvfoi7ylk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:msg-smile-filled" /></template>
