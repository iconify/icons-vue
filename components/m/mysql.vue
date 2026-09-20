<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6mvytb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6mvytb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mysql" /></template>
