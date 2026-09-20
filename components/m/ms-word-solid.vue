<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zknrt17wv.css';
import '../../css/o/oufzmac7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zknrt17wv"/><path clip-rule="evenodd" class="oufzmac7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ms-word-solid" /></template>
