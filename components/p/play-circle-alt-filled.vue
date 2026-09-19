<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnv37kbxp.css';
import '../../css/r/r-mn_3bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnv37kbxp"/><path class="r-mn_3bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:play-circle-alt-filled" /></template>
