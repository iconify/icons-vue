<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-k06jxyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-k06jxyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ventilator-alt-outline-24px" /></template>
