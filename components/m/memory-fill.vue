<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrcnnyuzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrcnnyuzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:memory-fill" /></template>
