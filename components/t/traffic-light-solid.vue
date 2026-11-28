<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubqgkl9kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubqgkl9kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:traffic-light-solid" /></template>
