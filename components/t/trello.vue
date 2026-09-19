<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zibk1xbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zibk1xbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:trello" /></template>
