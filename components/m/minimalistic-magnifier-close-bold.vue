<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-5f2htjo.css';
import '../../css/y/yq54glb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-5f2htjo"/><path clip-rule="evenodd" class="yq54glb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-close-bold" /></template>
