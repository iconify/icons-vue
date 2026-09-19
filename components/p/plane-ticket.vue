<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs99ztb-t.css';
import '../../css/m/mcbwykhxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs99ztb-t"/><path class="mcbwykhxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:plane-ticket" /></template>
