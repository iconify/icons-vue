<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf1qn4z0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf1qn4z0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-arrange-above" /></template>
