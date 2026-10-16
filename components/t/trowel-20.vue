<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgd5ds6is.css';
import '../../css/i/i1nkquj9v.css';
import '../../css/u/u9bld2bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zgd5ds6is"/><path class="i1nkquj9v"/><path class="u9bld2bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trowel-20" /></template>
