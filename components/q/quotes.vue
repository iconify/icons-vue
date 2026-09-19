<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4v-hpbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="l4v-hpbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:quotes" /></template>
