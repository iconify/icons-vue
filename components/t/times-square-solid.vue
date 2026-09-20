<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3nu8lbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3nu8lbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:times-square-solid" /></template>
