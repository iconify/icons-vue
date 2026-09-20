<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejc422bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejc422bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:moleculer" /></template>
