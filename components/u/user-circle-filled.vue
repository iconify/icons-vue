<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgd1oobnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qgd1oobnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-circle-filled" /></template>
