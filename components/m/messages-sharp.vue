<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwrbtvvyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwrbtvvyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:messages-sharp" /></template>
