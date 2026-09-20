<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5odgwb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5odgwb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-tip-line" /></template>
