<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_iv6r6-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_iv6r6-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:video-call-x" /></template>
