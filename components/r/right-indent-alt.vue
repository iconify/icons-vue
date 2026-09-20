<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzs_ybc9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzs_ybc9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:right-indent-alt" /></template>
