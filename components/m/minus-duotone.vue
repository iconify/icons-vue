<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1osvpbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v1osvpbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:minus-duotone" /></template>
