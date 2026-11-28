<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnc1wrb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnc1wrb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-0" /></template>
