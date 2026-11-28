<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7te-jbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7te-jbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sofa" /></template>
