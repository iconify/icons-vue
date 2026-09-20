<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh8dv8nts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh8dv8nts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:playstation2" /></template>
