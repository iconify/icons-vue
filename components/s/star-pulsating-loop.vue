<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp45jb.css';
import '../../css/d/d-t9c80f.css';
import '../../css/s/so-from-34.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp45jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-pulsating-loop" /></template>
