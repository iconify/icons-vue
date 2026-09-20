<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h262zsh8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h262zsh8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:scrollreveal" /></template>
