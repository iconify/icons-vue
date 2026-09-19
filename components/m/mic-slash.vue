<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_0pz_gks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="k_0pz_gks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:mic-slash" /></template>
