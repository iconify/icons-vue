<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_a1tbc-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_a1tbc-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:stage-light-group" /></template>
