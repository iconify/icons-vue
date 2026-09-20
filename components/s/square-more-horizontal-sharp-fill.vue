<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/murjnlnua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="murjnlnua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-more-horizontal-sharp-fill" /></template>
