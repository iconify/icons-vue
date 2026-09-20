<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/racnh6jjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="racnh6jjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:usergroup-clear-filled" /></template>
