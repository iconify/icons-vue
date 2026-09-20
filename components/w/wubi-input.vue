<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gojy3tzbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gojy3tzbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wubi-input" /></template>
