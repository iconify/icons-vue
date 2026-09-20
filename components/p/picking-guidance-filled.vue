<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq8hgbwan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eq8hgbwan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:picking-guidance-filled" /></template>
