<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi91kyoxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yi91kyoxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:paint-bucket-solid" /></template>
