<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szmru1bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="szmru1bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:weight" /></template>
