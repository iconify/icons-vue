<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn4hvs1rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn4hvs1rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:science" /></template>
