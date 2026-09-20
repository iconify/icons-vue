<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2_dl55yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2_dl55yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:metaai" /></template>
