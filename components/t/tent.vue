<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po4ve2bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po4ve2bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tent" /></template>
