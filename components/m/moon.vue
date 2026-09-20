<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n31jkrbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n31jkrbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:moon" /></template>
