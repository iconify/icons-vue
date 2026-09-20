<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udqjs3box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udqjs3box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:stackframe-fill" /></template>
