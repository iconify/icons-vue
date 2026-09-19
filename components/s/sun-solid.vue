<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4qi6ywjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4qi6ywjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:sun-solid" /></template>
