<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh_af3ezb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh_af3ezb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:quarantine-place-hospital" /></template>
