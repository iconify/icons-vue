<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kimoq7uac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="kimoq7uac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:verticalborder" /></template>
