<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_8azubyy.css';
import '../../css/u/ur2-jsh4j.css';
import '../../css/t/te90o_idu.css';
import '../../css/y/y3kxq9bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_8azubyy"/><path clip-rule="evenodd" class="ur2-jsh4j"/><path class="te90o_idu"/><path clip-rule="evenodd" class="y3kxq9bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pin-list-bold" /></template>
