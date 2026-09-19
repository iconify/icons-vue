<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8db4pmpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8db4pmpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:truenas-logo" /></template>
