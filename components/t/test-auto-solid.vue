<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkq06-bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nkq06-bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:test-auto-solid" /></template>
