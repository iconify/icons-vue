<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap9ynib2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ap9ynib2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:medical-cross-symbol-solid" /></template>
