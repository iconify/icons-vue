<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf7of2bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gf7of2bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:mouse2-fill" /></template>
