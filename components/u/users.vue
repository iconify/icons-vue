<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh7s0061t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh7s0061t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:users" /></template>
