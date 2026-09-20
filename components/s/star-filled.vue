<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8-d7z.css';
import '../../css/m/mnwdzw.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-34.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8-d7z"/><path class="mnwdzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-filled" /></template>
