<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9v855hut.css';
import '../../css/x/xs8ua7-4a.css';
import '../../css/c/c_yb27byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9v855hut"/><path class="xs8ua7-4a"/><path class="c_yb27byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-nuclear-48" /></template>
