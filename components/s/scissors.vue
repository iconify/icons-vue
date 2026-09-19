<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb-zycb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hb-zycb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:scissors" /></template>
