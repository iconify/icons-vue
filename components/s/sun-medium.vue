<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hll8w5bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hll8w5bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-medium" /></template>
