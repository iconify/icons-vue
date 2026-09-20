<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4bmxbc0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4bmxbc0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opensea" /></template>
