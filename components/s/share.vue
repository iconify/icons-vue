<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9u0zxhna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y9u0zxhna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:share" /></template>
