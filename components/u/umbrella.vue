<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_nu_bb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_nu_bb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:umbrella" /></template>
