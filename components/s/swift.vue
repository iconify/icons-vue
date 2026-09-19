<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkdvgsboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkdvgsboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:swift" /></template>
