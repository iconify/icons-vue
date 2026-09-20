<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ino_babvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ino_babvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mlk" /></template>
