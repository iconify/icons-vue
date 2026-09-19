<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiqfwabog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uiqfwabog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ticket" /></template>
