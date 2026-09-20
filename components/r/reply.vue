<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4orm5d6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v4orm5d6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:reply" /></template>
