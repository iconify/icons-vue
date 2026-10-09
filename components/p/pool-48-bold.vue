<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3p0zqbmw.css';
import '../../css/b/bl9mhqw5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b3p0zqbmw"/><path class="bl9mhqw5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pool-48-bold" /></template>
