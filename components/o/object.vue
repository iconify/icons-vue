<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki6y_ubzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ki6y_ubzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:object" /></template>
