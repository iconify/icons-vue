<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqfv4kcrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oqfv4kcrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:text-description" /></template>
