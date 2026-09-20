<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnimwlbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnimwlbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-intersection" /></template>
