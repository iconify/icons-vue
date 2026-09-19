<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvm7s_btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dvm7s_btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sun-dust" /></template>
