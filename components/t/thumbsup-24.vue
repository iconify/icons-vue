<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzmq702cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzmq702cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:thumbsup-24" /></template>
