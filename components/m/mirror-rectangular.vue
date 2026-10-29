<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1tt9fb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1tt9fb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mirror-rectangular" /></template>
