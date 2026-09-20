<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evn_o6jvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evn_o6jvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:row-remove" /></template>
