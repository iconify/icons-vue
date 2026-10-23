<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx6z_rr9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx6z_rr9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shell" /></template>
