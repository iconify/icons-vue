<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmx_sxbxs.css';
import '../../css/c/c582bi82c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kmx_sxbxs"/><path class="c582bi82c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:test-tube-fill-20" /></template>
