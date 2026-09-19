<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpq-wsbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kpq-wsbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:person-private-outline" /></template>
