<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irm3f4b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="irm3f4b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:radio" /></template>
