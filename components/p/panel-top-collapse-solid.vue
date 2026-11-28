<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czurdaczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czurdaczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:panel-top-collapse-solid" /></template>
