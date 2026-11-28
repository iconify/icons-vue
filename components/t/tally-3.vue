<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmp9qmbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmp9qmbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-3" /></template>
