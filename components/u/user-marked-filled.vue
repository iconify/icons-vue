<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_dd1bcgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_dd1bcgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-marked-filled" /></template>
