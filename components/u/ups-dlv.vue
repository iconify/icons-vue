<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_lxb5bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_lxb5bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ups-dlv" /></template>
