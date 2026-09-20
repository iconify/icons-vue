<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr-5-vblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr-5-vblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:paperplane-duotone" /></template>
