<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zej7lmbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zej7lmbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trash" /></template>
