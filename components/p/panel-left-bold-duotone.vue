<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy6caez-r.css';
import '../../css/e/es2bfhexf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wy6caez-r"/><path class="es2bfhexf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-bold-duotone" /></template>
