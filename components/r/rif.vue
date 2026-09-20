<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq9_55bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq9_55bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rif" /></template>
