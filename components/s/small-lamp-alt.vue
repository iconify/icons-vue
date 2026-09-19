<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqh79mb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqh79mb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:small-lamp-alt" /></template>
