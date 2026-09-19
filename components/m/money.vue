<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4vov5u3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4vov5u3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:money" /></template>
