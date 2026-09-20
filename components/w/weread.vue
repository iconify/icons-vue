<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4du2hnfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4du2hnfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:weread" /></template>
