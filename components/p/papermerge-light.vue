<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dky8cybzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dky8cybzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermerge-light" /></template>
