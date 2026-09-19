<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-altxbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="p-altxbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:meteor" /></template>
