<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgnxe6t6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fgnxe6t6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-at" /></template>
