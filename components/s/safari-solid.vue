<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy3n31i7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cy3n31i7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:safari-solid" /></template>
