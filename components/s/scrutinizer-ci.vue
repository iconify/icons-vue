<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9j5b1edd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9j5b1edd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:scrutinizer-ci" /></template>
