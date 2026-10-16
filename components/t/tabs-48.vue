<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar2h8rs6u.css';
import '../../css/f/fd1yhqbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ar2h8rs6u"/><path class="fd1yhqbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tabs-48" /></template>
