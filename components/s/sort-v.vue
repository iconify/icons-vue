<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pueogv6az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pueogv6az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort-v" /></template>
