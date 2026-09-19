<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnmm_rbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jnmm_rbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:picarto-tv" /></template>
