<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdh-lqh4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xdh-lqh4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-perspective-outline" /></template>
