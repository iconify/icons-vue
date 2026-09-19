<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zexqi29dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zexqi29dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:umbrella-alt" /></template>
