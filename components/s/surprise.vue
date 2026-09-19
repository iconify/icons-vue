<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm_2ikbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":698};
const content = `<path class="mm_2ikbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:surprise" /></template>
