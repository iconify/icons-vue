<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baavd1mxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baavd1mxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mails-fill" /></template>
