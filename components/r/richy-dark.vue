<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h363pobgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h363pobgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:richy-dark" /></template>
