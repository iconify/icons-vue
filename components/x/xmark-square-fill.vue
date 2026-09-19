<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh_5xqbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xh_5xqbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:xmark-square-fill" /></template>
