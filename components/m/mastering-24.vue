<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg372g3ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yg372g3ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mastering-24" /></template>
