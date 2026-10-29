<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhhr4kvhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhhr4kvhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:watch-solid" /></template>
