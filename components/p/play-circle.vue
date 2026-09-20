<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze8c43b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze8c43b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:play-circle" /></template>
