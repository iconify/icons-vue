<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn_uf6bnc.css';
import '../../css/i/ivhxmubfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bn_uf6bnc"/><path class="ivhxmubfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-check-fill-20" /></template>
