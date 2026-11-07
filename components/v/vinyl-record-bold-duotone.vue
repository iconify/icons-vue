<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b85oo4swx.css';
import '../../css/f/fdq8872og.css';
import '../../css/q/q14qdhbhn.css';
import '../../css/k/kjtd21bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b85oo4swx"/><path class="fdq8872og"/><path class="q14qdhbhn"/><path clip-rule="evenodd" class="kjtd21bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:vinyl-record-bold-duotone" /></template>
