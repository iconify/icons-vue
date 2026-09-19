<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odg8d7b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odg8d7b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:musical-notes" /></template>
