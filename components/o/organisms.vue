<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z026_tbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z026_tbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:organisms" /></template>
