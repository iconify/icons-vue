<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbcc0f97s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbcc0f97s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:zz" /></template>
