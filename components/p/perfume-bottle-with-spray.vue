<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4nsh49nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s4nsh49nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:perfume-bottle-with-spray" /></template>
