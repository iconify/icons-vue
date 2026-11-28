<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab_-r-boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab_-r-boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:package-minus-solid" /></template>
