<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf2_ehdun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jf2_ehdun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:thumbdown" /></template>
