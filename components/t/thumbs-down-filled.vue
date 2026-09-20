<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy4-bn.css';
import '../../css/t/t7y_kz.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-76.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy4-bn"/><path class="t7y_kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:thumbs-down-filled" /></template>
