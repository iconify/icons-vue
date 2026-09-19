<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glkv8ob8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="glkv8ob8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:scalpel" /></template>
