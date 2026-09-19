<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2czy9tvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2czy9tvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:maximize-alt" /></template>
