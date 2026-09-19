<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiry2_s1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yiry2_s1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:menu" /></template>
