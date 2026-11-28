<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvkvv28pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvkvv28pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pear-solid" /></template>
