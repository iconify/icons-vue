<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp40cv00c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp40cv00c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-circle-gear" /></template>
