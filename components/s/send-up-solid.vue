<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1giy57js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="j1giy57js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:send-up-solid" /></template>
