<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oexiugx6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path clip-rule="evenodd" class="oexiugx6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-github" /></template>
