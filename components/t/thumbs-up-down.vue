<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czmq92zwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czmq92zwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:thumbs-up-down" /></template>
