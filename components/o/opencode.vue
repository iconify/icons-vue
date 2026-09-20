<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8bnafpqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8bnafpqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:opencode" /></template>
