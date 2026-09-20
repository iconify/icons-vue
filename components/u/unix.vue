<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgj4jib6k.css';
import '../../css/h/h5p52qoon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgj4jib6k"/><path class="h5p52qoon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:unix" /></template>
