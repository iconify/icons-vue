<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh-hi-1jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh-hi-1jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:social-distancing-protect-shield-2" /></template>
