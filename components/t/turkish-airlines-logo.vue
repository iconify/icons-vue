<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj1teub4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj1teub4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:turkish-airlines-logo" /></template>
