<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hel45b33c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="hel45b33c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:stapler" /></template>
