<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbacixbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bbacixbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:stata" /></template>
