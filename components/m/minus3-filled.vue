<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myf67vu-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myf67vu-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minus3-filled" /></template>
