<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcw1domtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcw1domtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:running" /></template>
