<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnr9zi33a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-1};
const content = `<path class="tnr9zi33a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:medal" /></template>
