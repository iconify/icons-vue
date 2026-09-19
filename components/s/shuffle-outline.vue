<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr2b31b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr2b31b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:shuffle-outline" /></template>
