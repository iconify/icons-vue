<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udkn3mb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="udkn3mb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:pencil" /></template>
