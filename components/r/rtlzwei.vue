<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awui1tb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awui1tb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rtlzwei" /></template>
