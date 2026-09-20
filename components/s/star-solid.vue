<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in0jig21n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in0jig21n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:star-solid" /></template>
