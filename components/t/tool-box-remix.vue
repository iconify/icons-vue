<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev_271blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ev_271blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:tool-box-remix" /></template>
