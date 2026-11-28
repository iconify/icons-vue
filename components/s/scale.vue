<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa55io0tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa55io0tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:scale" /></template>
