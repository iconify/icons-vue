<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob_t6ubko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ob_t6ubko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:puzzle" /></template>
