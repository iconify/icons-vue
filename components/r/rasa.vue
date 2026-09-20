<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0by00bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0by00bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rasa" /></template>
