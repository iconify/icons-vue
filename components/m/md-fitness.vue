<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we_skjcpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="we_skjcpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-fitness" /></template>
