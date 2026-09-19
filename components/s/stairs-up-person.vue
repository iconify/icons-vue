<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0c6ssbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0c6ssbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:stairs-up-person" /></template>
