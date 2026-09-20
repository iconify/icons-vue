<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adnoxa.css';
import '../../css/s/so-from-38.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adnoxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:play" /></template>
