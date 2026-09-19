<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei9w6ufyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ei9w6ufyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:texture" /></template>
