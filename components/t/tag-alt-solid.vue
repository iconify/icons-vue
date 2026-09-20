<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7p-uactz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g7p-uactz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:tag-alt-solid" /></template>
