<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjkn6nbgz.css';
import '../../css/b/boa7bx3yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjkn6nbgz"/><path class="boa7bx3yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:recive-square-bold-duotone" /></template>
