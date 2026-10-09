<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9-5dabgd.css';
import '../../css/x/x-j00pe6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p9-5dabgd"/><path class="x-j00pe6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-lock-20" /></template>
