<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j71h0-ger.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j71h0-ger"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:panel-ipc" /></template>
