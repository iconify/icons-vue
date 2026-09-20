<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktu5yu9_t.css';
import '../../css/i/iwm0m9oaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ktu5yu9_t"/><path class="iwm0m9oaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:snippet-16" /></template>
