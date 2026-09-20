<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqqaunmgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqqaunmgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:plus-square-fill" /></template>
