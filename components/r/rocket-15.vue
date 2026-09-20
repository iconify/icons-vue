<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btf34qj2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="btf34qj2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:rocket-15" /></template>
