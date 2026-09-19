<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy02c7b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy02c7b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:phone-hangup-solid" /></template>
