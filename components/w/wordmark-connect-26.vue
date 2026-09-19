<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8hfccbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":85,"height":26};
const content = `<path class="p8hfccbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-connect-26" /></template>
