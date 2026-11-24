<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm8jd1bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm8jd1bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stone-filled" /></template>
