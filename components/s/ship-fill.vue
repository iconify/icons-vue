<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7y2tcb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7y2tcb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ship-fill" /></template>
