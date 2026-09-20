<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flvqiw0bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flvqiw0bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:prek" /></template>
