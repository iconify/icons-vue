<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pks9adckk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1664};
const content = `<path class="pks9adckk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:music" /></template>
