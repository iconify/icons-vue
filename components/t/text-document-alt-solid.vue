<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phivkab6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="phivkab6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:text-document-alt-solid" /></template>
