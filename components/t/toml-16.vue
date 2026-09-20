<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnf3jj1ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jnf3jj1ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:toml-16" /></template>
