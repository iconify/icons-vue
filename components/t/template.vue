<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aienk9a9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="aienk9a9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:template" /></template>
