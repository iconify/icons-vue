<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkkt_je4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkkt_je4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-github" /></template>
