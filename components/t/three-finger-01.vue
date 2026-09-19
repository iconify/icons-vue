<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_85a_4sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_85a_4sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:three-finger-01" /></template>
