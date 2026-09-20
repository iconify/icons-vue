<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztx4bbczg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztx4bbczg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wallabag" /></template>
