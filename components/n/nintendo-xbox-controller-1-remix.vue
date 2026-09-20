<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz_n6bbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jz_n6bbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:nintendo-xbox-controller-1-remix" /></template>
