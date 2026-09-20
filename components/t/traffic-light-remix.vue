<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfv5b7b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gfv5b7b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:traffic-light-remix" /></template>
