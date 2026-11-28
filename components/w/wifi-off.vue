<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqj9z9wrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqj9z9wrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wifi-off" /></template>
