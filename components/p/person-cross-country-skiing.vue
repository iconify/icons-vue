<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/babhpbcia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="babhpbcia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-cross-country-skiing" /></template>
