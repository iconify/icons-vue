<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fek3nqbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fek3nqbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:pointer" /></template>
