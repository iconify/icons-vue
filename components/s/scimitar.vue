<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atcn-d_jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="atcn-d_jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:scimitar" /></template>
