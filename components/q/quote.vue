<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl8wdhw6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl8wdhw6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:quote" /></template>
