<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np5mjvb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np5mjvb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volume-low-filled" /></template>
