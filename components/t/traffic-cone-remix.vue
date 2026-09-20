<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2k3krd6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q2k3krd6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:traffic-cone-remix" /></template>
