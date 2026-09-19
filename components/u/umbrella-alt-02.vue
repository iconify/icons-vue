<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jllui1bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jllui1bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:umbrella-alt-02" /></template>
