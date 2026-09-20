<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg-dvgjit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fg-dvgjit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star-fall3" /></template>
