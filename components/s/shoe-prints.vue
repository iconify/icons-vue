<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3kt8y1qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="b3kt8y1qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shoe-prints" /></template>
