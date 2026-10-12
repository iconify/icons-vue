<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfcrsdfef.css';
import '../../css/o/ot8dm5bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfcrsdfef"/><path class="ot8dm5bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pill-bottle-filled" /></template>
