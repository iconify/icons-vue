<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v76w70e2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v76w70e2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:route" /></template>
