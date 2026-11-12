<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpzvbnz3y.css';
import '../../css/t/tkao4yftb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="vpzvbnz3y"/><path class="tkao4yftb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plain-week" /></template>
