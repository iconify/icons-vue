<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kadpm5bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kadpm5bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:minus" /></template>
