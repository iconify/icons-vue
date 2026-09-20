<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp60v3b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jp60v3b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:moustache-solid" /></template>
