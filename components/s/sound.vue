<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo1wiob4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":472};
const content = `<path class="jo1wiob4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:sound" /></template>
