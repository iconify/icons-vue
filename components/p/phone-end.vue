<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8c89mrxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z8c89mrxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-end" /></template>
