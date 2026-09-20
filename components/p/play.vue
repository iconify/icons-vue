<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykpl97bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-3};
const content = `<path class="ykpl97bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:play" /></template>
