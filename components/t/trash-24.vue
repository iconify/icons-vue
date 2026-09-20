<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu-junbcx.css';
import '../../css/j/jicrk8bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu-junbcx"/><path clip-rule="evenodd" class="jicrk8bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:trash-24" /></template>
