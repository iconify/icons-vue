<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2-z04aat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2-z04aat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sticky-note-minus" /></template>
