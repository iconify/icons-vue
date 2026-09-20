<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia2z1bcgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia2z1bcgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:thales" /></template>
