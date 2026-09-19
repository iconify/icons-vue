<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7u-_1bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z7u-_1bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:pipeline" /></template>
