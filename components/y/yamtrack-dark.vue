<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jch2jjbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jch2jjbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yamtrack-dark" /></template>
