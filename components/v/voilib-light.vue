<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lllp7cbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lllp7cbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voilib-light" /></template>
