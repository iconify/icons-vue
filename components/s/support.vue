<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs6sgts4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xs6sgts4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:support" /></template>
