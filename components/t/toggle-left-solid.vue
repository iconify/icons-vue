<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pssw4_ktq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pssw4_ktq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:toggle-left-solid" /></template>
