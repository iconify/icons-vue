<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd-f2dbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd-f2dbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:share-24" /></template>
