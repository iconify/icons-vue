<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqyuiws6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bqyuiws6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:object-align-justify-vertical" /></template>
