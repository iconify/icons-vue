<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svu75sbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svu75sbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:thefinals" /></template>
