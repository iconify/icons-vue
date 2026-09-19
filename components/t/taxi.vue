<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-k1b_1rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-k1b_1rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:taxi" /></template>
