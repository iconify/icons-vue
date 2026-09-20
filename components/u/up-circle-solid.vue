<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srui7osvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="srui7osvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:up-circle-solid" /></template>
