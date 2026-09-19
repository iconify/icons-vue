<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne4kifgai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne4kifgai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:ordored-list-outline" /></template>
