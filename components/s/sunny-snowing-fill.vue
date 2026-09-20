<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyrdmhb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyrdmhb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sunny-snowing-fill" /></template>
