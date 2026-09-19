<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-23bqbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-23bqbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:scissors" /></template>
