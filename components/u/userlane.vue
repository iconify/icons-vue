<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjz-x1bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjz-x1bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:userlane" /></template>
