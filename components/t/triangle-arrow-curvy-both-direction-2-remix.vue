<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bysje_byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bysje_byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:triangle-arrow-curvy-both-direction-2-remix" /></template>
