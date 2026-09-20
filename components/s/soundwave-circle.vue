<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt95cub8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kt95cub8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:soundwave-circle" /></template>
