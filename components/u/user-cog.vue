<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dct4eibpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dct4eibpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-cog" /></template>
