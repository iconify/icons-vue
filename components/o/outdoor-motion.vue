<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oksd2tbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oksd2tbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:outdoor-motion" /></template>
