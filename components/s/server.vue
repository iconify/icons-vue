<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzge0abfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pzge0abfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:server" /></template>
