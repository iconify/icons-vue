<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxab02pny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxab02pny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:no-gas-station" /></template>
