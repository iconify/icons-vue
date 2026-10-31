<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv78kg08c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv78kg08c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:package-open-gloss" /></template>
