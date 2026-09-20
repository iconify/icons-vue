<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x97qw9bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x97qw9bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:person" /></template>
