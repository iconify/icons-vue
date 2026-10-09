<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8cp6cb9j.css';
import '../../css/b/bqwp1jb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r8cp6cb9j"/><path class="bqwp1jb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refresh-20" /></template>
