<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyv8nfhqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyv8nfhqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wave-pulse" /></template>
