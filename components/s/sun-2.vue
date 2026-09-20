<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgyrhbboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgyrhbboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sun-2" /></template>
