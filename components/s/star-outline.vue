<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py1a31bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py1a31bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:star-outline" /></template>
