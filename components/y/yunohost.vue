<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lncqekgkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lncqekgkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:yunohost" /></template>
