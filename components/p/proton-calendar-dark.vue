<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_mutobdf.css';
import '../../css/b/bdz5tbc3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_mutobdf"/><path class="bdz5tbc3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proton-calendar-dark" /></template>
