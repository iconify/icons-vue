<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw5jzub_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw5jzub_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:pod" /></template>
