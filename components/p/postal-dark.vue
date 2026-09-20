<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqfxqwb8y.css';
import '../../css/v/vd40rwvyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqfxqwb8y"/><path class="vd40rwvyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:postal-dark" /></template>
