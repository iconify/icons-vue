<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy8nyytvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy8nyytvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:taxbuzz" /></template>
