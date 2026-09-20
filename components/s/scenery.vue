<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqa5odb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqa5odb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:scenery" /></template>
