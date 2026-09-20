<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj8wl0l1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj8wl0l1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-down" /></template>
