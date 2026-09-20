<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjx16568o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="wjx16568o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:share" /></template>
