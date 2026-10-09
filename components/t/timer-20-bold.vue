<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4i7afb6c.css';
import '../../css/z/zjxzq32mp.css';
import '../../css/s/s9gv9gb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o4i7afb6c"/><path class="zjxzq32mp"/><path class="s9gv9gb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:timer-20-bold" /></template>
