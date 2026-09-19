<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avnnhrb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="avnnhrb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-burst" /></template>
