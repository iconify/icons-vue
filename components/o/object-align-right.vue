<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab9w6cblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ab9w6cblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:object-align-right" /></template>
