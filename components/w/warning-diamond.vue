<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jid4_bb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jid4_bb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:warning-diamond" /></template>
