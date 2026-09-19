<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luegz3bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":427,"height":512};
const content = `<path class="luegz3bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nuclide" /></template>
