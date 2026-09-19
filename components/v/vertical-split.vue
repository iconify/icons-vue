<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgjojzb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgjojzb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:vertical-split" /></template>
