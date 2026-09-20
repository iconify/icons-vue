<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlc9yabgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zlc9yabgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-with-droplets" /></template>
