<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an54jmb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="an54jmb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:object-align-left" /></template>
