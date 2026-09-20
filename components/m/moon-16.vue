<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak_u2fnec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ak_u2fnec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:moon-16" /></template>
