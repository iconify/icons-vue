<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pipedab_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pipedab_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:minus" /></template>
