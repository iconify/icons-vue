<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1if_sxyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1if_sxyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rarible" /></template>
