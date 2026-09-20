<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjjo3sblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjjo3sblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:user-alt-4-line" /></template>
