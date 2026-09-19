<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhd497buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":650,"height":679};
const content = `<path class="vhd497buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:ustream" /></template>
