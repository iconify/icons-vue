<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwq-6ijup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwq-6ijup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:wondershare" /></template>
