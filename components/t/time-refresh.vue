<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-zr0lbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-zr0lbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:time-refresh" /></template>
