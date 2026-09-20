<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uii4qobww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uii4qobww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:share" /></template>
