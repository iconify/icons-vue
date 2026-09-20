<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pazkftbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pazkftbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:share-16" /></template>
