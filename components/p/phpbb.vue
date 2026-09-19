<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0rps6bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="m0rps6bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:phpbb" /></template>
