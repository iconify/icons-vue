<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o05uwt_pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o05uwt_pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:minimize-2" /></template>
