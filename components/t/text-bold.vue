<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6pk2lfov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f6pk2lfov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:text-bold" /></template>
