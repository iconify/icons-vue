<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m37772ano.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m37772ano"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:strikethrough" /></template>
