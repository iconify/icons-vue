<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yag1ve2fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yag1ve2fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:store" /></template>
