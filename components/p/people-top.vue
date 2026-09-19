<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4g7cd22t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a4g7cd22t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:people-top" /></template>
