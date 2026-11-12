<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rod24kbrj.css';
import '../../css/g/g_wa16mho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rod24kbrj"/><path class="g_wa16mho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:msgvault" /></template>
