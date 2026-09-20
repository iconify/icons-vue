<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cekqefb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cekqefb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:plus-circle-solid" /></template>
