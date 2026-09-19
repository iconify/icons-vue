<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq8_w3bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq8_w3bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-list-filled" /></template>
