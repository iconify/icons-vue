<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyrd3-bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wyrd3-bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:struct-16" /></template>
