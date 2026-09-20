<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpm6fm9qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpm6fm9qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:volleyball" /></template>
