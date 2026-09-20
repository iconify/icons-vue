<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhdsewb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jhdsewb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:retry" /></template>
