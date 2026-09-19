<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2i58labe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w2i58labe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:object-align-center-horizontal" /></template>
