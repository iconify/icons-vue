<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkljsib1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tkljsib1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:signal-full-solid" /></template>
