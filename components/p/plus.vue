<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee36auwua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ee36auwua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:plus" /></template>
