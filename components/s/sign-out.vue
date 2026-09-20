<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npx1l6b-f.css';
import '../../css/c/cywx5ebns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="npx1l6b-f"/><path class="cywx5ebns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:sign-out" /></template>
