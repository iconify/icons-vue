<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9uwov.css';
import '../../css/s/so-from-62.css';
import '../../css/t/tr-b5mmly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9uwov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:phone-loop" /></template>
