<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl8jdu0bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl8jdu0bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-discount" /></template>
