<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab5hjefrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ab5hjefrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:triangle" /></template>
