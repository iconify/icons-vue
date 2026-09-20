<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_8arlbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_8arlbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:vector-arrange-above" /></template>
