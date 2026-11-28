<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6m7u3bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6m7u3bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:motorbike" /></template>
