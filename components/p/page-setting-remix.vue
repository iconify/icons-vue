<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he8gb17ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="he8gb17ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:page-setting-remix" /></template>
