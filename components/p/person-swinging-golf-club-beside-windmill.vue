<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-3huhbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k-3huhbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-swinging-golf-club-beside-windmill" /></template>
