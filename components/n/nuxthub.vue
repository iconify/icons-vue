<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxeyuembw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49,"height":33};
const content = `<path clip-rule="evenodd" class="bxeyuembw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nuxthub" /></template>
