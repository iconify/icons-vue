<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7-7_jn-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7-7_jn-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medical-flask" /></template>
