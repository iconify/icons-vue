<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkn0u6z1h.css';
import '../../css/z/zcm3eh2ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qkn0u6z1h"/><path class="zcm3eh2ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-plus-stroke-20" /></template>
