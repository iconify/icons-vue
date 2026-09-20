<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrw8l6u1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw8l6u1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:xbox-live-logo" /></template>
