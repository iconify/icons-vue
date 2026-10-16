<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9oan5bbl.css';
import '../../css/c/c65-ehvfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v9oan5bbl"/><path class="c65-ehvfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smog-48" /></template>
