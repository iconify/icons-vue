<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka2xyrbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ka2xyrbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-tick-solid" /></template>
