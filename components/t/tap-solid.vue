<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peeffdmla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peeffdmla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tap-solid" /></template>
