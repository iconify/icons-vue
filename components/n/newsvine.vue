<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqzm5abuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":488};
const content = `<path class="zqzm5abuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:newsvine" /></template>
