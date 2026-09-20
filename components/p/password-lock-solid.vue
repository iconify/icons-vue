<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq6m08ces.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gq6m08ces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:password-lock-solid" /></template>
