<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9fzqcbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="c9fzqcbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:store" /></template>
