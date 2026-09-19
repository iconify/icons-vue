<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-nwy9zre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c-nwy9zre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:market" /></template>
