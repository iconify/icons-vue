<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjzxuveym.css';
import '../../css/f/foygadfek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qjzxuveym"/><path class="foygadfek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:modal-list" /></template>
