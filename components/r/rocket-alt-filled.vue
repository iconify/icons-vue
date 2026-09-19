<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mycr2h52x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mycr2h52x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rocket-alt-filled" /></template>
