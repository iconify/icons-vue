<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz609_phz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz609_phz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:number-2" /></template>
