<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn09w3stf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn09w3stf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:siren-alt" /></template>
