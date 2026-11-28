<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwmvxg2bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwmvxg2bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-refresh" /></template>
