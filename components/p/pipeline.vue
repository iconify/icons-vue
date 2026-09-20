<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr-e1ac-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sr-e1ac-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:pipeline" /></template>
