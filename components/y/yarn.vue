<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-k9udc6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-k9udc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:yarn" /></template>
