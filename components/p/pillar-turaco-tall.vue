<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb4fi6bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb4fi6bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pillar-turaco-tall" /></template>
