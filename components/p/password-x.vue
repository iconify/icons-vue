<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgzwr9b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgzwr9b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:password-x" /></template>
