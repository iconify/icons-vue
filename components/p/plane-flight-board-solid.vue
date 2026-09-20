<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcveprb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xcveprb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:plane-flight-board-solid" /></template>
