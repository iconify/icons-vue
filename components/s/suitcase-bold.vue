<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt01zo83t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jt01zo83t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suitcase-bold" /></template>
