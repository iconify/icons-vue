<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8s66ibcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8s66ibcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-duocolor-round" /></template>
