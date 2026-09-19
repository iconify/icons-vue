<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4ih49jxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4ih49jxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:ubuntu" /></template>
