<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj0wl3bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":12};
const content = `<path class="bj0wl3bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:medium" /></template>
