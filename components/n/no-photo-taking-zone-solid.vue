<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbtom9bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cbtom9bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:no-photo-taking-zone-solid" /></template>
