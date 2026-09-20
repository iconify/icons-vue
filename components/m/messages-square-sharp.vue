<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sov4fmbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sov4fmbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:messages-square-sharp" /></template>
