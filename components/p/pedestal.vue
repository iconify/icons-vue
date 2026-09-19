<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeapzsbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qeapzsbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pedestal" /></template>
