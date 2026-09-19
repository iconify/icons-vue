<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiozq7bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiozq7bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:moon-alt" /></template>
