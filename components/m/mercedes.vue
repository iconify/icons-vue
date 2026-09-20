<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l05vmnrsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l05vmnrsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mercedes" /></template>
