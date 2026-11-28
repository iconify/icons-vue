<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozuqne_mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozuqne_mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:more-horizontal-solid" /></template>
