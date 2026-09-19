<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w85_snbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w85_snbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:xing-filled" /></template>
