<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9cqm39fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b9cqm39fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reservoir-20-bold" /></template>
