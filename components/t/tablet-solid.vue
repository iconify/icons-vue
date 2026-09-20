<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7o9e3bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="v7o9e3bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:tablet-solid" /></template>
