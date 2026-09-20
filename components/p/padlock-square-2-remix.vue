<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pem9t_bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pem9t_bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:padlock-square-2-remix" /></template>
