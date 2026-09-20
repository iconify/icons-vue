<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4mo4nolz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f4mo4nolz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:share-link-remix" /></template>
