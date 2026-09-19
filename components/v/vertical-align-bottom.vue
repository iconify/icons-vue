<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_qnajo-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q_qnajo-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:vertical-align-bottom" /></template>
