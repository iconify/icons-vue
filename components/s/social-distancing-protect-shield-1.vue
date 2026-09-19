<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcvmx_b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcvmx_b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:social-distancing-protect-shield-1" /></template>
