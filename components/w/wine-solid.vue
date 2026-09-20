<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duw7_rf-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="duw7_rf-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wine-solid" /></template>
