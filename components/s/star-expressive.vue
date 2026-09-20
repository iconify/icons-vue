<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1cc8abnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c1cc8abnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:star-expressive" /></template>
