<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noj5714vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noj5714vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mixpanel" /></template>
