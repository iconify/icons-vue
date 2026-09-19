<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k52lsdbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="k52lsdbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:paste" /></template>
