<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrhv1bcks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrhv1bcks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tablet-x" /></template>
