<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p94-ao1ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p94-ao1ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:picking-filled" /></template>
