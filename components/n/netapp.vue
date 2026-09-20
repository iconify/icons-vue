<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjys986ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjys986ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:netapp" /></template>
