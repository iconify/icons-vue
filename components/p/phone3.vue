<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t__cc02fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t__cc02fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone3" /></template>
