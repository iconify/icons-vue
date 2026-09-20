<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4_vhgc-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4_vhgc-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-bad-line" /></template>
