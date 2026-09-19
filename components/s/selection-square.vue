<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw8hk2oxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cw8hk2oxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:selection-square" /></template>
