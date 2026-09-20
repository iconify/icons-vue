<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7apwdq2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7apwdq2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-user-fill" /></template>
