<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l74d4lbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l74d4lbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu-right-alt" /></template>
