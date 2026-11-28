<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpk7p9tnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qpk7p9tnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:orbit-duotone" /></template>
