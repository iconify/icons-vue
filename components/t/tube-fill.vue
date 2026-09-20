<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy8j3sb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy8j3sb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:tube-fill" /></template>
