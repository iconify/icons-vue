<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ootoywbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":24};
const content = `<path class="ootoywbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:rainbow" /></template>
