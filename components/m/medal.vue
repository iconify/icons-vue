<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kscjx21xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kscjx21xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:medal" /></template>
