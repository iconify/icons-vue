<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7i7wkb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u7i7wkb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:simit-macro-component-editor" /></template>
