<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng5_5oycj.css';
import '../../css/p/pt5wbdc-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ng5_5oycj"/><path class="duoicon-primary-layer pt5wbdc-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:smartphone-vibration" /></template>
