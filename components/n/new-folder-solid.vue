<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb2cbhbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bb2cbhbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:new-folder-solid" /></template>
