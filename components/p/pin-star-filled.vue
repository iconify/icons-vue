<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlowtv98h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vlowtv98h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-star-filled" /></template>
