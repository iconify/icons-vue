<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et_p2rb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et_p2rb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:taki" /></template>
