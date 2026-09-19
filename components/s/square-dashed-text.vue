<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkqbgz0qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xkqbgz0qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-dashed-text" /></template>
