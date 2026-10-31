<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afmco4o4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="afmco4o4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:outdent-16-solid" /></template>
