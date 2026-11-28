<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc7r85hdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc7r85hdd primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spool-duotone" /></template>
