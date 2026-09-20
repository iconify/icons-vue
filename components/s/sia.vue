<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3w9xceup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3w9xceup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:sia" /></template>
