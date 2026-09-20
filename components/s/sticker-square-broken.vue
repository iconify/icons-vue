<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9xxhfe6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9xxhfe6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-square-broken" /></template>
