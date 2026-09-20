<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl75c2-_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl75c2-_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:traffic-cone-line" /></template>
