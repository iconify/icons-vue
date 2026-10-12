<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3hqbvbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f3hqbvbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-circle-fill-20" /></template>
