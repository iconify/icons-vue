<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv64medta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv64medta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:medical-drip" /></template>
