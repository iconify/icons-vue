<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9if2ebze.css';
import '../../css/e/eog-i8bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h9if2ebze"/><path class="eog-i8bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stapler-20" /></template>
