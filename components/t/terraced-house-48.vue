<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc7h1ybso.css';
import '../../css/s/saf2gf3kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bc7h1ybso"/><path class="saf2gf3kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:terraced-house-48" /></template>
