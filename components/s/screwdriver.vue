<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c40pz5bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c40pz5bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:screwdriver" /></template>
