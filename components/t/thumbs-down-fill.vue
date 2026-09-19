<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myhk15bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="myhk15bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:thumbs-down-fill" /></template>
