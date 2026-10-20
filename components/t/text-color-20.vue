<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dld0-6buw.css';
import '../../css/b/bdj9pbbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dld0-6buw"/><path class="bdj9pbbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-color-20" /></template>
