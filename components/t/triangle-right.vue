<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyrz-1ftw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyrz-1ftw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-right" /></template>
