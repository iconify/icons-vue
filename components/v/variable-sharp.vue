<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6v10ib0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6v10ib0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:variable-sharp" /></template>
