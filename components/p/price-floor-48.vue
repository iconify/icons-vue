<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utf77lbef.css';
import '../../css/b/b3uqkjboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="utf77lbef"/><path class="b3uqkjboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-floor-48" /></template>
