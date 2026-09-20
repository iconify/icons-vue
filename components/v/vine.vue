<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbibp0bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbibp0bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vine" /></template>
