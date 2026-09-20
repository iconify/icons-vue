<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbsipg4pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbsipg4pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:roadmapdotsh" /></template>
