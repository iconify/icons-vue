<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt38cn2hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt38cn2hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pencil-sketch" /></template>
