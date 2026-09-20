<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2pc4ebwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2pc4ebwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:terminal-light" /></template>
