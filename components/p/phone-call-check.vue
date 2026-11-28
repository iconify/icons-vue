<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp-p80w9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp-p80w9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:phone-call-check" /></template>
