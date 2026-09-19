<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phes-ab4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phes-ab4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:opnsense" /></template>
