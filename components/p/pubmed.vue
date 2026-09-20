<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmar4pbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmar4pbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pubmed" /></template>
