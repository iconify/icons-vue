<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz64nmlvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz64nmlvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:svgtrace" /></template>
