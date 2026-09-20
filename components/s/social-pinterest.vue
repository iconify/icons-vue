<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj6s_8m8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":976};
const content = `<path class="hj6s_8m8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-pinterest" /></template>
