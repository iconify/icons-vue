<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y92s1mbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y92s1mbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:zoom" /></template>
