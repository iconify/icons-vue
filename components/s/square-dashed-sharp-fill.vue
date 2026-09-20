<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bplkplbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bplkplbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-dashed-sharp-fill" /></template>
