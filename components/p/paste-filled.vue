<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdmzv2bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pdmzv2bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:paste-filled" /></template>
