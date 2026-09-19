<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oflcx7bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oflcx7bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-receive-01" /></template>
