<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxpgxd99y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxpgxd99y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:notebook-1" /></template>
