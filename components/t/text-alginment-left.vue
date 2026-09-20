<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3zl63b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u3zl63b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:text-alginment-left" /></template>
