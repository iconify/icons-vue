<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0cksp2iz.css';
import '../../css/x/xcjnzfb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0cksp2iz"/><path class="xcjnzfb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:parentheses-bold-duotone" /></template>
