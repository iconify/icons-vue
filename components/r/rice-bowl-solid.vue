<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3v3w2n_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3v3w2n_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rice-bowl-solid" /></template>
