<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4rf0mbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q4rf0mbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:refused-24px" /></template>
