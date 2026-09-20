<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcl0_1bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mcl0_1bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-vert-circle-fill" /></template>
